<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flncb6b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="flncb6b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:broadcast" /></template>
