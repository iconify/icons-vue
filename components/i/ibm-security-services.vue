<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_u1exb-p.css';
import '../../css/h/hbx_zybzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j_u1exb-p"/><path class="hbx_zybzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-security-services" /></template>
