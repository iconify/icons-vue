<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_lq4bvop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="p_lq4bvop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:head-side-mask" /></template>
