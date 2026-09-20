<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssoyox_pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ssoyox_pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-upright-empty" /></template>
