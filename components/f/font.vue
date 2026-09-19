<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkutg_bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jkutg_bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:font" /></template>
