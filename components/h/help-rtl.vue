<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqy99db8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iqy99db8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:help-rtl" /></template>
