<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orcy-v-bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="orcy-v-bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dumbbell" /></template>
