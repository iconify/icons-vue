<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpnki8bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jpnki8bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:half-alpha" /></template>
