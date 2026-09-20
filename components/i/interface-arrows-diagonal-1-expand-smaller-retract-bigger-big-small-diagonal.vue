<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv8qdukki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dv8qdukki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-diagonal-1-expand-smaller-retract-bigger-big-small-diagonal" /></template>
