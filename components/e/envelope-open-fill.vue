<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2ji2r33e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t2ji2r33e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:envelope-open-fill" /></template>
