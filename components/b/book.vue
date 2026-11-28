<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lys6u4jad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lys6u4jad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book" /></template>
