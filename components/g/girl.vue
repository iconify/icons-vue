<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgl2kc_3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mgl2kc_3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:girl" /></template>
