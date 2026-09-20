<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8d_vgbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m8d_vgbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bluetooth-searching-solid" /></template>
