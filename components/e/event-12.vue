<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_0ygnbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w_0ygnbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:event-12" /></template>
