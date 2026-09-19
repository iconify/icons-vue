<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qps999guh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qps999guh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bold-stroke-12" /></template>
