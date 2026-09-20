<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amviyhbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amviyhbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:archicad" /></template>
