<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg4qi0d9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="zg4qi0d9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:link" /></template>
