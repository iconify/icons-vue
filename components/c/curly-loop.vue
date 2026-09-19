<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et4ql6hmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="et4ql6hmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:curly-loop" /></template>
