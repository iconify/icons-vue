<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1yv8q8vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="y1yv8q8vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:alarm-add" /></template>
