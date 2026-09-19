<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcv4s00xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcv4s00xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:leaf" /></template>
