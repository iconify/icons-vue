<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqmaehbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqmaehbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:canonical" /></template>
