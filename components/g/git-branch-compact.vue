<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuw8d-xuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kuw8d-xuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:git-branch-compact" /></template>
