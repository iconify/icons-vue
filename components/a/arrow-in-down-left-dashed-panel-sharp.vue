<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvd1w9bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvd1w9bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-down-left-dashed-panel-sharp" /></template>
