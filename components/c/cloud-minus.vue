<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgk3ygrzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgk3ygrzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-minus" /></template>
