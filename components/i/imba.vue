<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn896ebbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":201,"height":201};
const content = `<path class="dn896ebbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:imba" /></template>
