<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s19vr9ebe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s19vr9ebe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:broken-link-2" /></template>
