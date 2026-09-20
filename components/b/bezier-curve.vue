<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej_v4pv_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ej_v4pv_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:bezier-curve" /></template>
