<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulk_7v2hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulk_7v2hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:forestry" /></template>
