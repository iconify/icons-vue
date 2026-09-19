<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq1twmhyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qq1twmhyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-thumb-down-16-solid" /></template>
