<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6ucwcbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u6ucwcbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:insert" /></template>
