<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szu_-8m4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szu_-8m4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:conduwuit-dark" /></template>
