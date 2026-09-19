<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiuw0lbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":464};
const content = `<path class="xiuw0lbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:fire" /></template>
