<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7cu_u-yk.css';
import '../../css/p/p351x--2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x7cu_u-yk"/><circle class="p351x--2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:blender" /></template>
