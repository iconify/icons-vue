<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d56l13zdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="d56l13zdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-remove-bold" /></template>
