<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3mdx591i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u3mdx591i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:drawing-document-filled" /></template>
