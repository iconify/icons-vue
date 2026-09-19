<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvlro3bdf.css';
import '../../css/w/whiyyb3wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qvlro3bdf"/><path class="whiyyb3wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-pdf" /></template>
