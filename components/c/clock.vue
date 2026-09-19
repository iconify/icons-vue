<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh5h3cber.css';
import '../../css/y/yzwsfcckq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qh5h3cber"/><path class="yzwsfcckq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:clock" /></template>
