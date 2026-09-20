<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csjoy6p0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="csjoy6p0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-down-right" /></template>
