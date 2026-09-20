<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifutwnbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ifutwnbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-diagonal-2-expand-smaller-retract-bigger-big-small-diagonal" /></template>
