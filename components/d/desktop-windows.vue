<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqk3hhf6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":432};
const content = `<path class="rqk3hhf6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:desktop-windows" /></template>
