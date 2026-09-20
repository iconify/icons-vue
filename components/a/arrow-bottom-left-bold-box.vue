<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v63uistmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v63uistmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-left-bold-box" /></template>
