<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_neeqb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":220};
const content = `<path class="e_neeqb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:json-schema" /></template>
