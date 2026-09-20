<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6n6q2but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6n6q2but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-csv-outline" /></template>
