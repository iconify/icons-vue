<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv4b38b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":408};
const content = `<path class="kv4b38b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bus" /></template>
