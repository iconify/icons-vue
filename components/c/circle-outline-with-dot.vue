<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpr3jrk0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lpr3jrk0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circle-outline-with-dot" /></template>
