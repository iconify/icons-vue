<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atz9pabfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":440};
const content = `<path class="atz9pabfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:hdr-off" /></template>
