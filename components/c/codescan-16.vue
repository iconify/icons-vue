<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3kcy-bcr.css';
import '../../css/u/uqoc3xb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r3kcy-bcr"/><path class="uqoc3xb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:codescan-16" /></template>
