<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-qwv2pri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-qwv2pri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitcoin-light" /></template>
