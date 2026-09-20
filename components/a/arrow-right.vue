<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh1bo_vog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh1bo_vog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-right" /></template>
