<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-49-9v2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v-49-9v2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-up-left" /></template>
