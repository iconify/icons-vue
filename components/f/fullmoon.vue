<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm63k1bpv.css';
import '../../css/g/ggrxmcksm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fm63k1bpv"/><path class="ggrxmcksm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:fullmoon" /></template>
