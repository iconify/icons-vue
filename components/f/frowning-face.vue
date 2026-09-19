<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3e7prykc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f3e7prykc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:frowning-face" /></template>
