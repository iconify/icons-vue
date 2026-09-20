<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bspjx2xhr.css';
import '../../css/x/xje7wbbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bspjx2xhr"/><path class="xje7wbbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:amex" /></template>
