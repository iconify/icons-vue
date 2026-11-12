<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj6b63bfc.css';
import '../../css/j/jiywhnbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yj6b63bfc"/><path class="jiywhnbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chibisafe-light" /></template>
