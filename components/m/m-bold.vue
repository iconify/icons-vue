<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsuvst8qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="dsuvst8qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:m-bold" /></template>
