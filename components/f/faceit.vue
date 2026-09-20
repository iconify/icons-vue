<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfn29bgpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfn29bgpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:faceit" /></template>
