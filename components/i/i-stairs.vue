<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th42spb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="th42spb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-stairs" /></template>
