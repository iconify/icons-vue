<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti2jc9bbd.css';
import '../../css/p/p1sjyybhn.css';
import '../../css/o/onse16b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ti2jc9bbd"/><path class="p1sjyybhn"/><path class="onse16b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-medical-records" /></template>
