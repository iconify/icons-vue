<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrd_hrbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrd_hrbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-box-minus-outline" /></template>
