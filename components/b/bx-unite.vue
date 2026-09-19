<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz8difb4r.css';
import '../../css/q/qne2hd_ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz8difb4r"/><path class="qne2hd_ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-unite" /></template>
