<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6t-gvgwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e6t-gvgwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:event" /></template>
