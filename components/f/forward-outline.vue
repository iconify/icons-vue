<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dneqsibml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dneqsibml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:forward-outline" /></template>
