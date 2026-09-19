<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2qs83soi.css';
import '../../css/e/ea7_acb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2qs83soi"/><path class="ea7_acb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:history" /></template>
