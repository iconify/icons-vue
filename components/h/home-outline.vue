<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxp_s1b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxp_s1b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:home-outline" /></template>
