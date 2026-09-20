<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf5_y917j.css';
import '../../css/u/ub1z-yb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf5_y917j"/><path class="ub1z-yb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:lock-open-alt" /></template>
