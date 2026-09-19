<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgm3qwbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tgm3qwbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:instalod" /></template>
