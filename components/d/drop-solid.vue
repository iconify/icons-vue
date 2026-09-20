<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utzl12bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="utzl12bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:drop-solid" /></template>
