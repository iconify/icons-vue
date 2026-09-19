<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyv4gxb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="xyv4gxb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lastfm" /></template>
