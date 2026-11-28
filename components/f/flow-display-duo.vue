<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_si3tfrr.css';
import '../../css/e/edghc2bfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary z_si3tfrr"/><path class="edghc2bfh primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-display-duo" /></template>
