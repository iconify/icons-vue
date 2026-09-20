<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybsln6b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybsln6b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bookmark-light" /></template>
