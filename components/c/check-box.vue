<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-fdedcse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":360,"height":448};
const content = `<path class="d-fdedcse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:check-box" /></template>
