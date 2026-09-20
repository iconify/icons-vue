<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfneb3qce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nfneb3qce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-down-right-16" /></template>
