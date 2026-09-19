<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck2uatfas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ck2uatfas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:forward" /></template>
