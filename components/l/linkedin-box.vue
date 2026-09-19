<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rywumhb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="rywumhb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:linkedin-box" /></template>
