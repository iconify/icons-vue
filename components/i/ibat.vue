<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdk2ryvgs.css';
import '../../css/o/oxo9nw_dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdk2ryvgs"/><path class="oxo9nw_dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ibat" /></template>
