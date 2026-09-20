<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq_95nb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tq_95nb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chase" /></template>
