<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tibe2sbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tibe2sbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cetusguard-light" /></template>
