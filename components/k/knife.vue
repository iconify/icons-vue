<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl5954btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl5954btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:knife" /></template>
