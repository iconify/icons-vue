<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0ie7db7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c0ie7db7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:arrow-both" /></template>
