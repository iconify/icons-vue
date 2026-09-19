<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3etuu25j.css';
import '../../css/y/y5pksnbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3etuu25j"/><path class="y5pksnbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:baseball" /></template>
