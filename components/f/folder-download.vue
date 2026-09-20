<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugn75zu8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ugn75zu8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:folder-download" /></template>
