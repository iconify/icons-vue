<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_3tac-mi.css';
import '../../css/y/ygp2y4lsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":448};
const content = `<defs><path id="SVGx22VTcBv" class="v_3tac-mi"/></defs><use href="#SVGx22VTcBv"/><use href="#SVGx22VTcBv"/><path class="ygp2y4lsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:intlayer-light" /></template>
