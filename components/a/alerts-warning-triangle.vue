<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbdo17bye.css';
import '../../css/e/eag0spbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbdo17bye"/><path class="eag0spbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:alerts-warning-triangle" /></template>
