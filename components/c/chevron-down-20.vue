<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lezm_k3dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lezm_k3dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-down-20" /></template>
