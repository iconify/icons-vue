<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1u40bb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e1u40bb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:folder-put" /></template>
