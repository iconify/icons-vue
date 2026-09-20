<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1x38_bty.css';
import '../../css/l/l8zqkabzp.css';
import '../../css/s/su8twpfed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n1x38_bty"/><path class="l8zqkabzp"/><path class="su8twpfed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:alarm" /></template>
