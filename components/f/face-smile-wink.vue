<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnfb1u0jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pnfb1u0jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-smile-wink" /></template>
