<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2o82qbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n2o82qbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:link" /></template>
