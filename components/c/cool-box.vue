<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhk9d3brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qhk9d3brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cool-box" /></template>
