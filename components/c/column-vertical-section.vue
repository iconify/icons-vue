<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdv6r3b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qdv6r3b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:column-vertical-section" /></template>
