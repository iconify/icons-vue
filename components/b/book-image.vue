<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0v178b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="d0v178b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:book-image" /></template>
