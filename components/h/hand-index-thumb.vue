<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcpw23ryq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rcpw23ryq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hand-index-thumb" /></template>
