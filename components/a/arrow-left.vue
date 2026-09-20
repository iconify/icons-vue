<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0e2fqd9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="p0e2fqd9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:arrow-left" /></template>
