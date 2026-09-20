<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbiybx0vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbiybx0vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:imac-filled" /></template>
