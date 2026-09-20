<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey4o1_bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey4o1_bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bank-minus" /></template>
