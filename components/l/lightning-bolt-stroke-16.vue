<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qydy7ebjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qydy7ebjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lightning-bolt-stroke-16" /></template>
