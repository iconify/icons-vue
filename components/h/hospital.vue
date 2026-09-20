<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwqp5qbdv.css';
import '../../css/w/wi3s5ubtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jwqp5qbdv"/><path class="wi3s5ubtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hospital" /></template>
