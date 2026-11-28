<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkoq1acph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkoq1acph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fish-solid" /></template>
