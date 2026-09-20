<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mso5wcbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mso5wcbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:copy-rtl" /></template>
