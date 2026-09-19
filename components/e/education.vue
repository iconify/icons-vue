<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su8f1hu3j.css';
import '../../css/r/r6zc52b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="su8f1hu3j"/><path class="r6zc52b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:education" /></template>
