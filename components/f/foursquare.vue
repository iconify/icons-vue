<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m721o8_8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m721o8_8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:foursquare" /></template>
