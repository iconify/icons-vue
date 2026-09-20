<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf5xyob1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf5xyob1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-check-sharp-fill" /></template>
