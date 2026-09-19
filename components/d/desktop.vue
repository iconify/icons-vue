<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3gyc7_cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="p3gyc7_cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:desktop" /></template>
