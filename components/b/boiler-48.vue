<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_kcw3bme.css';
import '../../css/z/zryj4abdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l_kcw3bme"/><path class="zryj4abdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:boiler-48" /></template>
