<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv2q9dqxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nv2q9dqxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:baseball" /></template>
