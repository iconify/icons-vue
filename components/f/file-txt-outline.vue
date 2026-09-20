<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn5q14rop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nn5q14rop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-txt-outline" /></template>
