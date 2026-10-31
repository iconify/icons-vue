<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwl1g1bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwl1g1bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:divider-small-duocolor-round" /></template>
