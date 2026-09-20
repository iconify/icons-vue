<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4fy8gbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4fy8gbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:baseball-ball" /></template>
