<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys4-ebc3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ys4-ebc3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-code-16" /></template>
