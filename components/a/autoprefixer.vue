<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tseu1abac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tseu1abac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:autoprefixer" /></template>
