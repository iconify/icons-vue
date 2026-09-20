<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8z5k-bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8z5k-bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-bigquery" /></template>
