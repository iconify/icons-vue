<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnrmsfh-l.css';
import '../../css/h/hdnx13uec.css';
import '../../css/r/ruvlv2d2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gnrmsfh-l"/><path class="hdnx13uec"/><path class="ruvlv2d2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cross-seed" /></template>
