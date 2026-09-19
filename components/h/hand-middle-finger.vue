<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuvhuy_rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iuvhuy_rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-middle-finger" /></template>
