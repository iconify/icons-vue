<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7f_54bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="i7f_54bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:eyeclose" /></template>
