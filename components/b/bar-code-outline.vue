<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttzr14bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ttzr14bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:bar-code-outline" /></template>
