<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr0xo5b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr0xo5b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:json-web-tokens" /></template>
