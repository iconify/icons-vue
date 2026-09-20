<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v21qiwb4s.css';
import '../../css/s/s59rn4bzl.css';
import '../../css/b/bx_cywb5v.css';
import '../../css/v/vniimhb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v21qiwb4s"/><path class="s59rn4bzl"/><path class="bx_cywb5v"/><path class="vniimhb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-kanban-linear" /></template>
