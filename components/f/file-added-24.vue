<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh6xlccjr.css';
import '../../css/o/o-szn7-xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh6xlccjr"/><path class="o-szn7-xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-added-24" /></template>
