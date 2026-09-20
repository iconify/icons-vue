<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbboz65cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbboz65cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chrome-web-store" /></template>
