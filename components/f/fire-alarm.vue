<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xatu0ybou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xatu0ybou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:fire-alarm" /></template>
