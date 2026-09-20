<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukc4lr9sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ukc4lr9sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:dail-pad" /></template>
