<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmepz7blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wmepz7blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aleph" /></template>
