<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-nx7_bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-nx7_bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:credit-card-refresh" /></template>
