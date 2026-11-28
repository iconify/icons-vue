<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjr09ebid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjr09ebid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-turkish-lira-solid" /></template>
