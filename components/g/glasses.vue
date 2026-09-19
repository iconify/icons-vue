<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iouf7kbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="iouf7kbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:glasses" /></template>
