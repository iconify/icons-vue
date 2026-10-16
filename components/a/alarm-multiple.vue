<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/metz4187g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="metz4187g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:alarm-multiple" /></template>
