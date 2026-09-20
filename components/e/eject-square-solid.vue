<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frmldq4_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="frmldq4_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:eject-square-solid" /></template>
