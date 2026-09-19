<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn4rg314c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="vn4rg314c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cloud-circle" /></template>
