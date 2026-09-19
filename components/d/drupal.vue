<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbbhu27xv.css';
import '../../css/x/xhhedbbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbbhu27xv"/><path class="xhhedbbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:drupal" /></template>
