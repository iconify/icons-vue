<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-1j1wbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-1j1wbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-2-horizontal-line" /></template>
