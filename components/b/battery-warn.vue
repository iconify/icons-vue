<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th7uwt0-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="th7uwt0-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-warn" /></template>
