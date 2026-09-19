<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x05pc-vgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x05pc-vgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:arpdown" /></template>
