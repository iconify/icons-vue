<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gap8vwbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gap8vwbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:beaker-filled" /></template>
