<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xty0e4bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xty0e4bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calls-incoming" /></template>
