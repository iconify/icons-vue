<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9i0gw1ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="r9i0gw1ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:baht-sign" /></template>
