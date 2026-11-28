<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n13t0cbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n13t0cbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard" /></template>
