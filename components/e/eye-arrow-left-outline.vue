<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1y3p7bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1y3p7bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eye-arrow-left-outline" /></template>
