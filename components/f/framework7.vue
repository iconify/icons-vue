<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_oeyvb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_oeyvb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:framework7" /></template>
