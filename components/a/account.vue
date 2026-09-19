<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9hqy1byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="r9hqy1byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:account" /></template>
