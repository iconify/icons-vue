<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fld9aqiof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fld9aqiof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hon" /></template>
