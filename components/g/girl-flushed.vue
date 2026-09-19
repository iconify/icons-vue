<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md3g2pqyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="md3g2pqyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-flushed" /></template>
