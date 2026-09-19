<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8jnr3b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":440};
const content = `<path class="n8jnr3b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:layers-off" /></template>
