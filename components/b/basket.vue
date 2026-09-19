<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow7i0tzjj.css';
import '../../css/s/s47q5obuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow7i0tzjj"/><path class="s47q5obuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:basket" /></template>
