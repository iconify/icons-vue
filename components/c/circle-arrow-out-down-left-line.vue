<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj_ymgb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj_ymgb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-arrow-out-down-left-line" /></template>
