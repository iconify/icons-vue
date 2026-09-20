<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u96yjjgeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u96yjjgeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:control-outline" /></template>
