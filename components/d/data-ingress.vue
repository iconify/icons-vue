<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_m-5vevq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_m-5vevq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:data-ingress" /></template>
