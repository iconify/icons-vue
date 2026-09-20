<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wotr4_fsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wotr4_fsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:leaves" /></template>
