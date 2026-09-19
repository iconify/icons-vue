<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj0om06rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gj0om06rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:blue-circle" /></template>
