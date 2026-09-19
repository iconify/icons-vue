<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnv6cykfw.css';
import '../../css/j/jjf3s4bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnv6cykfw"/><path class="jjf3s4bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:blender" /></template>
