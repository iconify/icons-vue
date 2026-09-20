<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnghrpb1d.css';
import '../../css/b/by4txvb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnghrpb1d"/><path class="by4txvb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:clock-nine" /></template>
