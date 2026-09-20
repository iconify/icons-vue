<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3oj49b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z3oj49b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:broken-link-2-solid" /></template>
