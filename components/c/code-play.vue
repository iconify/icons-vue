<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zesyah_yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zesyah_yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:code-play" /></template>
