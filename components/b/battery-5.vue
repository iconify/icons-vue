<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0k5xydhj.css';
import '../../css/h/h0r0o6bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n0k5xydhj"/><path class="h0r0o6bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:battery-5" /></template>
