<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1gf8xb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a1gf8xb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:chevron-up" /></template>
