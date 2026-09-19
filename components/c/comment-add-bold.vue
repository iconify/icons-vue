<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8bxd7bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="e8bxd7bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-add-bold" /></template>
