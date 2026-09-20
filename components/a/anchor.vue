<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz8m0tb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tz8m0tb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:anchor" /></template>
