<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfafurbwi.css';
import '../../css/v/vbceozjtn.css';
import '../../css/q/qu8h2tbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfafurbwi"/><path class="vbceozjtn"/><path class="qu8h2tbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-1-filled" /></template>
