<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq4tfvbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aq4tfvbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:fishing-angle" /></template>
