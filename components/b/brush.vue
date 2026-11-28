<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mniy60bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mniy60bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:brush" /></template>
