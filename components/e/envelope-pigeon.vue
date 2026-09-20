<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohbffsb_w.css';
import '../../css/t/tj55anbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohbffsb_w"/><path class="tj55anbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:envelope-pigeon" /></template>
