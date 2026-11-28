<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-600_bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-600_bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:circle-8" /></template>
