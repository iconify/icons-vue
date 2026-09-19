<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3uhq0alc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":605,"height":680};
const content = `<path class="r3uhq0alc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bookmark" /></template>
