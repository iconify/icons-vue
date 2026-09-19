<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up39y0b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="up39y0b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-xmark" /></template>
