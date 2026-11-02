<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzt3dg0_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzt3dg0_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-press-line" /></template>
