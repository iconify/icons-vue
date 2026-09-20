<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn_xh9bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn_xh9bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:douban-fill" /></template>
