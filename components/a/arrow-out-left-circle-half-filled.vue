<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo07tbb9o.css';
import '../../css/j/jgmlxzbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo07tbb9o"/><path class="jgmlxzbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-left-circle-half-filled" /></template>
