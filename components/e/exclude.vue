<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oexwgpb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oexwgpb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:exclude" /></template>
