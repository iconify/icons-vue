<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkm-nia1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkm-nia1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cart-1" /></template>
