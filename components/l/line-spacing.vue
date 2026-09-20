<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhnelib0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhnelib0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:line-spacing" /></template>
