<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or70u-m3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or70u-m3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-e-hexagon-solid" /></template>
