<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_z_s6grm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_z_s6grm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ceiling-lamp-fill" /></template>
