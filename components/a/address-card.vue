<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsuz01gsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fsuz01gsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:address-card" /></template>
