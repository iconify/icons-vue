<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb-7dubgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gb-7dubgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-top-left-solid-8" /></template>
