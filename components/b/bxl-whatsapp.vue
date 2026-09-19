<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn2rljbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mn2rljbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-whatsapp" /></template>
