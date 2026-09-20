<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8e6ve2du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8e6ve2du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:credit-card" /></template>
