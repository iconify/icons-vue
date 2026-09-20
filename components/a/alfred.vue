<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh98j-4dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh98j-4dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alfred" /></template>
