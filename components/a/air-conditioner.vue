<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n02t0mgcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n02t0mgcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:air-conditioner" /></template>
