<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh3dbhbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh3dbhbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ease-curve-control-points" /></template>
