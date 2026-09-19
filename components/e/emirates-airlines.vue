<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvr21dbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvr21dbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:emirates-airlines" /></template>
