<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0hblizrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r0hblizrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:inbox-16" /></template>
