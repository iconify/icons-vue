<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpl4gmb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="wpl4gmb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hands" /></template>
