<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f51nmvb9n.css';
import '../../css/t/t2aiwobxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f51nmvb9n"/><path class="t2aiwobxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder-shared" /></template>
