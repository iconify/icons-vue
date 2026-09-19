<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr-6bxncg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr-6bxncg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:laptop-device" /></template>
