<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xece1n4yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xece1n4yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:elevator" /></template>
