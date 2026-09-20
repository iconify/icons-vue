<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1u97zgbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g1u97zgbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-ignored-16" /></template>
