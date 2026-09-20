<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih7wdcbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ih7wdcbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:backlight" /></template>
