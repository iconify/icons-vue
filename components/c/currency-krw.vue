<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oli8uhmhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oli8uhmhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-krw" /></template>
