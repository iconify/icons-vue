<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hckomzb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hckomzb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:direction-left" /></template>
