<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avu4mnt9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="avu4mnt9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:linux" /></template>
