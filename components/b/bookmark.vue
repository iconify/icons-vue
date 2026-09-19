<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax1am94cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ax1am94cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:bookmark" /></template>
