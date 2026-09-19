<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg5e70b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hg5e70b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:digg" /></template>
