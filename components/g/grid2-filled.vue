<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybvsl1p_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybvsl1p_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid2-filled" /></template>
