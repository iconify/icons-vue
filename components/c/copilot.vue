<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf7zolb1b.css';
import '../../css/l/l6ei140ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jf7zolb1b"/><path class="l6ei140ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:copilot" /></template>
