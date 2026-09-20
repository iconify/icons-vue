<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1-9lubmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1-9lubmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ltspice" /></template>
