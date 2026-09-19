<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k393ltima.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k393ltima"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-e1-rsd-m1" /></template>
