<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tleo8_bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tleo8_bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:dial-finger-1-bold" /></template>
