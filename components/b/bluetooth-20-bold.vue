<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8m4h0bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v8m4h0bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bluetooth-20-bold" /></template>
