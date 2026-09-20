<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb2jjab7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wb2jjab7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:celcius" /></template>
