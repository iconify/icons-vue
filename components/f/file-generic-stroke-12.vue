<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyel1qbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="eyel1qbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-generic-stroke-12" /></template>
