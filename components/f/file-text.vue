<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7wfuwb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f7wfuwb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-text" /></template>
