<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2o_zuh-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2o_zuh-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-circle-selection-01" /></template>
