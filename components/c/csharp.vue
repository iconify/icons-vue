<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1aui4bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x1aui4bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:csharp" /></template>
