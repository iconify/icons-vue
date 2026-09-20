<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhto3bqyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhto3bqyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:control-radiobutton" /></template>
