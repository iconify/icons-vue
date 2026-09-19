<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze76x5b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ze76x5b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:code" /></template>
