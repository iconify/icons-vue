<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9o3_3bkw.css';
import '../../css/w/wmzc81bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9o3_3bkw"/><path class="wmzc81bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-left-arrow" /></template>
