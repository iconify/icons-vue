<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkxpisqwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkxpisqwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:boxing-line" /></template>
