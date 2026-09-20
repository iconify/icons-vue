<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efeqagbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efeqagbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-capacity-increase" /></template>
