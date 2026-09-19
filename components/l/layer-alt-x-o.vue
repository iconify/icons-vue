<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymjpdm2-p.css';
import '../../css/h/ha1q3jlnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ymjpdm2-p"/><path class="ha1q3jlnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-alt-x-o" /></template>
