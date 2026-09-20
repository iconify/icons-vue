<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gls8srdxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gls8srdxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:champagne-bottle-and-champagne-glass" /></template>
