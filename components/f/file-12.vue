<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmj32gb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cmj32gb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-12" /></template>
