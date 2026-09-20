<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddpn2rbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ddpn2rbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-round-up-left" /></template>
