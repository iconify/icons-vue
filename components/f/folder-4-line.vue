<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm3u1cb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm3u1cb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-4-line" /></template>
