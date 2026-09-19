<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8reapder.css';
import '../../css/a/ail0khy-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v8reapder"/><path class="ail0khy-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:drone" /></template>
