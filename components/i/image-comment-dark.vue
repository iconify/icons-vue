<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jne4o1brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jne4o1brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:image-comment-dark" /></template>
