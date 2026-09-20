<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnw_gdc9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnw_gdc9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:columns-2-fill" /></template>
