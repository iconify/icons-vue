<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt9os31ki.css';
import '../../css/o/ox5bagm_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt9os31ki"/><path class="ox5bagm_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:clinic" /></template>
