<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbc9zibtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nbc9zibtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:link-16" /></template>
