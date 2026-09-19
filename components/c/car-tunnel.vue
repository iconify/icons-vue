<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-m5keb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f-m5keb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:car-tunnel" /></template>
