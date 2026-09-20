<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co5oh0yvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co5oh0yvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bug-pause" /></template>
