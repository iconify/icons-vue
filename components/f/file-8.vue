<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c64j2fb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c64j2fb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-8" /></template>
