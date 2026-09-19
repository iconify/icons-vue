<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocd8hrmmu.css';
import '../../css/q/qosfk73sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ocd8hrmmu"/><path class="qosfk73sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:industry" /></template>
