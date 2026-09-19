<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qou-94boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qou-94boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:car-sport" /></template>
