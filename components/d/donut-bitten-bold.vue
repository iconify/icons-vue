<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4wd7-nbs.css';
import '../../css/j/jrqzroung.css';
import '../../css/x/xbekolb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4wd7-nbs"/><path class="jrqzroung"/><path clip-rule="evenodd" class="xbekolb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:donut-bitten-bold" /></template>
