<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jenw87wgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jenw87wgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ai" /></template>
