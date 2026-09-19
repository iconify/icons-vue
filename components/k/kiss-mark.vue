<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1os19l5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b1os19l5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:kiss-mark" /></template>
