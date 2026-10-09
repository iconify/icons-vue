<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfgux_bnw.css';
import '../../css/c/cnwk2jbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rfgux_bnw"/><path class="cnwk2jbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inbox-20-bold" /></template>
