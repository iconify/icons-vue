<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq7i1rv2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq7i1rv2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hcl" /></template>
