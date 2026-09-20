<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpi5w_ocz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpi5w_ocz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-plus" /></template>
