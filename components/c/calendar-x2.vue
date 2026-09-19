<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddgx_yb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddgx_yb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-x2" /></template>
