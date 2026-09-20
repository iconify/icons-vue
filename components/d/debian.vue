<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq5_t2bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oq5_t2bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:debian" /></template>
