<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mti7fqblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mti7fqblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:air-france" /></template>
