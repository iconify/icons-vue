<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iypdcyvhg.css';
import '../../css/u/ue-60pbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iypdcyvhg"/><path class="ue-60pbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:loop" /></template>
