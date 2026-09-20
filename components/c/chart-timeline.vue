<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccwuv1wgp.css';
import '../../css/a/anaf4rr2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ccwuv1wgp"/><path class="anaf4rr2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chart-timeline" /></template>
