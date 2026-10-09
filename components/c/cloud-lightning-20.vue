<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf4h7lvmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lf4h7lvmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-lightning-20" /></template>
