<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vphx_6btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vphx_6btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-ordered-az" /></template>
