<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4-_f1bng.css';
import '../../css/c/ccwmrkkue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z4-_f1bng"/><path class="ccwmrkkue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folders-48" /></template>
