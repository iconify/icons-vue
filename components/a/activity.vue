<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdzksmb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zdzksmb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:activity" /></template>
