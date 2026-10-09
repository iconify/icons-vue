<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1_q84b1c.css';
import '../../css/f/fzhucbcoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1_q84b1c"/><path class="fzhucbcoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bowling-20-bold" /></template>
