<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j82ck6b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j82ck6b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:h-circle" /></template>
