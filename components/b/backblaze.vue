<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib5vjhz9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib5vjhz9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:backblaze" /></template>
