<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz32weafm.css';
import '../../css/t/tawx_qbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="iz32weafm"/><path class="tawx_qbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:circle-minus" /></template>
