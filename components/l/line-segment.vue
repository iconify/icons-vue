<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff_gfrblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff_gfrblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:line-segment" /></template>
