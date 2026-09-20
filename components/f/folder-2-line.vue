<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeke05bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeke05bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-2-line" /></template>
