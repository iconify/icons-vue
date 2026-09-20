<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytn98r1le.css';
import '../../css/h/hijr5tbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ytn98r1le"/><path class="hijr5tbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chart" /></template>
