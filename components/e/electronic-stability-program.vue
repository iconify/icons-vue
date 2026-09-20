<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwzq31xlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwzq31xlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:electronic-stability-program" /></template>
