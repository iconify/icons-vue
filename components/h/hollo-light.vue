<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub_ceubfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ub_ceubfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hollo-light" /></template>
