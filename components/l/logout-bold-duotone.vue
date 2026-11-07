<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnqp7eb9p.css';
import '../../css/t/tsxl3yofp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnqp7eb9p"/><path clip-rule="evenodd" class="tsxl3yofp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:logout-bold-duotone" /></template>
