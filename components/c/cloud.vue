<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu4qu4p3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="fu4qu4p3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cloud" /></template>
