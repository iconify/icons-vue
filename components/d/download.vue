<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3b2fn1ti.css';
import '../../css/i/i_b6kebet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="r3b2fn1ti"/><path class="i_b6kebet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:download" /></template>
