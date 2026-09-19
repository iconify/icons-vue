<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6g7-gbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="i6g7-gbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:envelope-open" /></template>
