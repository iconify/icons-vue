<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzjb8eqmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mzjb8eqmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:column-vertical-section-edit" /></template>
