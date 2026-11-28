<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvxuy3bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvxuy3bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-graph-solid" /></template>
