<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sax2kubug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sax2kubug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:froward-1" /></template>
