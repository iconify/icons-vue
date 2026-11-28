<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxo5i7bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxo5i7bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:circle-0" /></template>
