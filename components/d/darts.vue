<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siwxp_b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siwxp_b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:darts" /></template>
