<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6t-qx8yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j6t-qx8yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-new" /></template>
