<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuj89ebij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuj89ebij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bubble-error" /></template>
