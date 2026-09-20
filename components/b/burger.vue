<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vy206ybjy.css';
import '../../css/f/fi4mx6jqq.css';
import '../../css/l/l7v7j6bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vy206ybjy"/><path class="fi4mx6jqq"/><path clip-rule="evenodd" class="l7v7j6bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:burger" /></template>
