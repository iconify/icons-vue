<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw8_z_2nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="iw8_z_2nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:circle-arrow-right" /></template>
