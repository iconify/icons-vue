<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmibc4bxr.css';
import '../../css/j/js89-w0oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="js89-w0oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:japan" /></template>
