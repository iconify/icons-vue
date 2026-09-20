<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggdcr0-jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ggdcr0-jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:karrot-light" /></template>
