<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsujgfxyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xsujgfxyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-up-stroke-16" /></template>
