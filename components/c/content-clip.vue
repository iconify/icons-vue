<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqooozbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eqooozbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-clip" /></template>
