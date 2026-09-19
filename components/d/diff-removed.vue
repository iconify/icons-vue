<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybo6i4clv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ybo6i4clv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:diff-removed" /></template>
