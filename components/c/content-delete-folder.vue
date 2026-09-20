<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvu_tubrj.css';
import '../../css/o/o9uqq6b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvu_tubrj"/><path clip-rule="evenodd" class="o9uqq6b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-delete-folder" /></template>
