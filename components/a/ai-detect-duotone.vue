<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzzh1ommd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qzzh1ommd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-detect-duotone" /></template>
