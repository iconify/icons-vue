<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfo-7vb2n.css';
import '../../css/t/tcdvgs_6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfo-7vb2n"/><path class="tcdvgs_6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:blind" /></template>
