<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgblcmbsv.css';
import '../../css/p/p_8a0397c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vgblcmbsv"/><path class="p_8a0397c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lips" /></template>
