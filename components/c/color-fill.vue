<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz8i1bs_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iz8i1bs_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:color-fill" /></template>
