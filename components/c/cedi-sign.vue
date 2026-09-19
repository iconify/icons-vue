<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waq7f_0of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="waq7f_0of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cedi-sign" /></template>
