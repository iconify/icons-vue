<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttqym4bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttqym4bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:air-conditioner-solid" /></template>
