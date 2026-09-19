<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4k4ixbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="b4k4ixbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:google-earth" /></template>
