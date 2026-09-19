<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmrsxwynv.css';
import '../../css/h/h4au9l6mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmrsxwynv"/><path class="h4au9l6mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:camera-outline" /></template>
