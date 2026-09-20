<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe_j1ac2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_j1ac2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ev-charger-ccs1" /></template>
