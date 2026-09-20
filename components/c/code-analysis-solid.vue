<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z23edu9ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z23edu9ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:code-analysis-solid" /></template>
