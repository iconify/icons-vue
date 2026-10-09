<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl2z74b1y.css';
import '../../css/l/lv3t6tmyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gl2z74b1y"/><path class="lv3t6tmyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-container-48" /></template>
