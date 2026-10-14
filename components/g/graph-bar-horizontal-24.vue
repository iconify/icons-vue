<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opchihbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opchihbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:graph-bar-horizontal-24" /></template>
