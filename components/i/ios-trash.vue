<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orc8djbsy.css';
import '../../css/s/s5lw05brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="orc8djbsy"/><path class="s5lw05brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-trash" /></template>
