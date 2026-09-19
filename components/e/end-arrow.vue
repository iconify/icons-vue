<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/galb7gc_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="galb7gc_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:end-arrow" /></template>
