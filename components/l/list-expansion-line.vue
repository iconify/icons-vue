<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-40_z1ey.css';
import '../../css/t/td92ekb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-40_z1ey"/><path class="td92ekb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-expansion-line" /></template>
