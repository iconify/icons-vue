<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdc6cpb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fdc6cpb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:library-building" /></template>
