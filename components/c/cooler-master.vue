<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxg0005bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxg0005bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cooler-master" /></template>
