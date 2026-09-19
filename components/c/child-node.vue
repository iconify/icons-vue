<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnq6rt34g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qnq6rt34g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:child-node" /></template>
