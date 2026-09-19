<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ckkjbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g1ckkjbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:email-stroke-16" /></template>
