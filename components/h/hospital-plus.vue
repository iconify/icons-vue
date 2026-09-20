<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddk_lrtal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddk_lrtal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:hospital-plus" /></template>
