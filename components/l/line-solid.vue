<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk6fdg-6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="wk6fdg-6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:line-solid" /></template>
