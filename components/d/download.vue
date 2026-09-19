<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpfudxb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xpfudxb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:download" /></template>
