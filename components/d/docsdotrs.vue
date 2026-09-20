<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frrvw0nro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frrvw0nro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:docsdotrs" /></template>
