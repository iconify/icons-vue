<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9k3_bcfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g9k3_bcfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux-dark" /></template>
