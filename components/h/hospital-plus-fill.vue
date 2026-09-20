<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kag72zbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kag72zbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:hospital-plus-fill" /></template>
