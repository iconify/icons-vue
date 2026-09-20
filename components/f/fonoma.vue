<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgt19h77j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgt19h77j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fonoma" /></template>
