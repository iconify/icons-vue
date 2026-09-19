<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqa3tkb1n.css';
import '../../css/m/mejvcfb8n.css';
import '../../css/t/t_n29sb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="mejvcfb8n"/><path class="t_n29sb1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:calendar-arrow-up-solid" /></template>
