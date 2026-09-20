<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i2z4fbcpe.css';
import '../../css/v/v21qiwb4s.css';
import '../../css/k/ku_qpobzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i2z4fbcpe"/><path class="v21qiwb4s"/><path class="ku_qpobzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-with-files-line-duotone" /></template>
