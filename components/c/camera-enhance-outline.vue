<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nigbbacpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nigbbacpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-enhance-outline" /></template>
