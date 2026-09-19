<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj_f8hdiy.css';
import '../../css/x/x7_q-qb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hj_f8hdiy"/><path class="x7_q-qb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ansible-wordmark" /></template>
