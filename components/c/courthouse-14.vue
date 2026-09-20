<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrphjs-2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wrphjs-2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:courthouse-14" /></template>
