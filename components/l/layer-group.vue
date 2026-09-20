<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncxrcbbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncxrcbbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:layer-group" /></template>
