<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wztl4rbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="wztl4rbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bar-11" /></template>
