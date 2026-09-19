<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvv8rja_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mvv8rja_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:constraint" /></template>
