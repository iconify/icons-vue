<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5ecocnoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t5ecocnoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:github-sponsors" /></template>
