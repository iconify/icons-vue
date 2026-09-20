<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytr_51bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="ytr_51bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-pull-request" /></template>
