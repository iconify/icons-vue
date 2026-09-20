<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs9w5vowg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hs9w5vowg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feedbase-dark" /></template>
