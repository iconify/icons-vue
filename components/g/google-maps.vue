<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymc-z9bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":480};
const content = `<path class="ymc-z9bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:google-maps" /></template>
