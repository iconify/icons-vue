<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t40y_0hxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t40y_0hxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-down-expressive" /></template>
