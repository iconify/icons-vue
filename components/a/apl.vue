<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w86o90byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":481,"height":512};
const content = `<path class="w86o90byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:apl" /></template>
