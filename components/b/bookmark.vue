<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc_vz2bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lc_vz2bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bookmark" /></template>
