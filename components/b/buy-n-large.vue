<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnnahnb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="pnnahnb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:buy-n-large" /></template>
