<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-p6cdbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-p6cdbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cooking-pot-clock" /></template>
