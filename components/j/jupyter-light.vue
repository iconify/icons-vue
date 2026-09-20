<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygxvezb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygxvezb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jupyter-light" /></template>
