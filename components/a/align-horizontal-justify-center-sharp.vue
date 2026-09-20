<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnu-rxwwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnu-rxwwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-justify-center-sharp" /></template>
