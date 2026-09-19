<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlb-er9ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jlb-er9ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:drop-of-blood" /></template>
