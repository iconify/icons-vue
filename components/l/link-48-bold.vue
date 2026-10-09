<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxsoire1d.css';
import '../../css/j/jy-i8_pkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kxsoire1d"/><path class="jy-i8_pkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:link-48-bold" /></template>
