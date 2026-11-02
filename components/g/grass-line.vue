<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rak7p_bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rak7p_bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grass-line" /></template>
