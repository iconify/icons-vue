<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3bstg6yn.css';
import '../../css/h/h4fi9ef0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r3bstg6yn"/><path class="h4fi9ef0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-commit-48" /></template>
