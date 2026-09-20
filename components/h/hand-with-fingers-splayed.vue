<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb1h0rm8o.css';
import '../../css/a/acwejz0_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tb1h0rm8o"/><path class="acwejz0_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hand-with-fingers-splayed" /></template>
