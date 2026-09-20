<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmn4a1b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fmn4a1b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dumpster-solid" /></template>
