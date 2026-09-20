<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tunlaubxi.css';
import '../../css/d/da5se5sef.css';
import '../../css/h/h01ydvy9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tunlaubxi"/><path class="da5se5sef"/><path class="h01ydvy9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ipfs-dark" /></template>
