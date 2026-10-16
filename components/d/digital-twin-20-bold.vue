<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr6w732hx.css';
import '../../css/a/aslqxg6fb.css';
import '../../css/f/fw_p-ryho.css';
import '../../css/c/cooiocbhc.css';
import '../../css/m/m_m_e8loz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gr6w732hx"/><path class="aslqxg6fb"/><path class="fw_p-ryho"/><path class="cooiocbhc"/><path class="m_m_e8loz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:digital-twin-20-bold" /></template>
