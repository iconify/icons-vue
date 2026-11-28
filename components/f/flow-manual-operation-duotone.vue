<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnv7t_j2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnv7t_j2w primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-manual-operation-duotone" /></template>
