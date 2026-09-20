<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr6zoej9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xr6zoej9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-add" /></template>
