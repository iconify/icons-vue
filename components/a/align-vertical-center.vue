<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qafr6ubam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="qafr6ubam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:align-vertical-center" /></template>
