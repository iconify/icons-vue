<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcqr4nb2y.css';
import '../../css/a/aruuerbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcqr4nb2y"/><path class="aruuerbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:headlamp" /></template>
