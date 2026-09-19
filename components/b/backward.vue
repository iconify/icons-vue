<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-6xlxb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="n-6xlxb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:backward" /></template>
