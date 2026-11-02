<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0vko-r_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0vko-r_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:full-moon-line" /></template>
