<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h648icg5m.css';
import '../../css/j/jvbru7b5c.css';
import '../../css/n/no4nwlbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h648icg5m"/><path class="jvbru7b5c"/><path class="no4nwlbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:drawing-compass" /></template>
