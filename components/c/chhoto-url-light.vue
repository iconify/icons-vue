<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhgf2cphm.css';
import '../../css/h/h_f86fbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fhgf2cphm"/><path class="h_f86fbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chhoto-url-light" /></template>
