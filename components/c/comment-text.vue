<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc9u30brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jc9u30brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:comment-text" /></template>
