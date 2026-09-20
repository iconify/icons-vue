<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-lmltbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e-lmltbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-block" /></template>
