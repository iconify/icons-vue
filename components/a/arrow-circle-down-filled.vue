<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wap3rr0uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wap3rr0uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-circle-down-filled" /></template>
