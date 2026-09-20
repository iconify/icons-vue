<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms_7ga3th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms_7ga3th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fila" /></template>
