<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5vwuc8im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v5vwuc8im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:google-play" /></template>
