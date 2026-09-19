<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbw0r8mbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbw0r8mbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:bar-chart" /></template>
