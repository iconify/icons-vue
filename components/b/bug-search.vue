<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc5g-k-ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc5g-k-ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bug-search" /></template>
