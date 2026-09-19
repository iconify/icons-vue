<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po20zu72v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="po20zu72v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:left-long" /></template>
