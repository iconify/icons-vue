<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a238j-m3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a238j-m3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:arrow-left" /></template>
