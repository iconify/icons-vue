<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou8cmbmfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou8cmbmfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hat-2-line" /></template>
