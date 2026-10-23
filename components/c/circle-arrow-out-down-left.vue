<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtlns_fvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtlns_fvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-arrow-out-down-left" /></template>
