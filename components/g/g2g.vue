<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8i2mzbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8i2mzbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:g2g" /></template>
