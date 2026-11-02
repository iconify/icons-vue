<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0z_f1ttz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0z_f1ttz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cake-slice-line" /></template>
