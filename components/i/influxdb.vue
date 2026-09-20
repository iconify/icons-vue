<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs7eezbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs7eezbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:influxdb" /></template>
