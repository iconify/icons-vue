<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq_yi2-xa.css';
import '../../css/g/gusqowxtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="dq_yi2-xa"/><path class="gusqowxtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:css-new" /></template>
