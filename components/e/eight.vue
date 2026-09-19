<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc5989hcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tc5989hcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eight" /></template>
