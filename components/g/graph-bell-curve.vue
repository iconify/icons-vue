<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xatenq_en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xatenq_en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:graph-bell-curve" /></template>
