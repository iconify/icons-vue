<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kja0_8b-p.css';
import '../../css/h/hbv47lb9l.css';
import '../../css/f/fcaf33b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kja0_8b-p"/><path class="hbv47lb9l"/><path class="fcaf33b7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-line-duotone" /></template>
