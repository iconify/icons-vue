<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsdibsc_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsdibsc_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flight-land-line" /></template>
