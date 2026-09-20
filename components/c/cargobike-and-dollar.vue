<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9g2p8bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l9g2p8bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-and-dollar" /></template>
