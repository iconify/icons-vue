<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjtj27bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjtj27bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:florist" /></template>
