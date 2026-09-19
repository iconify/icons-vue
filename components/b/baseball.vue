<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhp8qcbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhp8qcbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:baseball" /></template>
