<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4_utgbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="c4_utgbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:globe-with-meridians" /></template>
