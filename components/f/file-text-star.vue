<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqyuseboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqyuseboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-star" /></template>
