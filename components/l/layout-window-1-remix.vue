<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_l_2rugl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f_l_2rugl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:layout-window-1-remix" /></template>
