<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-ptz9fvg.css';
import '../../css/o/o04p_sbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-ptz9fvg"/><path class="o04p_sbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-square-half" /></template>
