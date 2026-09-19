<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcl56kzgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qcl56kzgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:infinite" /></template>
