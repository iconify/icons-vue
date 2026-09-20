<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9r4e7esb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9r4e7esb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:football-solid" /></template>
