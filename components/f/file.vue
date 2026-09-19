<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftndcxpdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ftndcxpdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:file" /></template>
