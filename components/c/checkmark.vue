<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqmj-2b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iqmj-2b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:checkmark" /></template>
