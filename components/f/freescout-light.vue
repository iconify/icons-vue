<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz27hpnpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":96,"height":96};
const content = `<path class="gz27hpnpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:freescout-light" /></template>
