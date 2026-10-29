<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q09nysnqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q09nysnqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:grip-horizontal-sketch" /></template>
