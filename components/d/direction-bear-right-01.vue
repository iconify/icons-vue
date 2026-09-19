<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp1h99b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cp1h99b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-bear-right-01" /></template>
