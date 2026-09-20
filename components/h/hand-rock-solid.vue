<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmm3h1b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jmm3h1b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-rock-solid" /></template>
