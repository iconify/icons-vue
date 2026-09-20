<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glxlc_bpl.css';
import '../../css/a/a2gr9fb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="glxlc_bpl"/><path class="a2gr9fb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-scisor" /></template>
