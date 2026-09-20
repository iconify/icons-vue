<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvs84zvzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvs84zvzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bottle-soda-classic-outline" /></template>
