<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl_lzhbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl_lzhbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:history" /></template>
