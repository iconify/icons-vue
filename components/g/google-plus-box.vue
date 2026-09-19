<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l27afibyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="l27afibyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:google-plus-box" /></template>
