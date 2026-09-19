<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ose1jpb8n.css';
import '../../css/h/hfzh1ebhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ose1jpb8n"/><path class="hfzh1ebhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-badge-check" /></template>
