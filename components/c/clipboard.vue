<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx80qc3zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx80qc3zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:clipboard" /></template>
