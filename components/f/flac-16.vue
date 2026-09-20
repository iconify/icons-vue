<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo4pizvlt.css';
import '../../css/u/u9pg7sbpc.css';
import '../../css/r/rd5o0ubin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fo4pizvlt"/><path clip-rule="evenodd" class="u9pg7sbpc"/><path class="rd5o0ubin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:flac-16" /></template>
