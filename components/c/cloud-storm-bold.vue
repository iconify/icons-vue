<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrctc3yce.css';
import '../../css/o/ow7qimb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrctc3yce"/><path class="ow7qimb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-storm-bold" /></template>
