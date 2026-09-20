<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbxme9fqn.css';
import '../../css/w/wi8y19aeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qbxme9fqn"/><path class="wi8y19aeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:expand-square" /></template>
