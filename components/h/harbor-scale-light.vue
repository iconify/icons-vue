<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw55blb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hw55blb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-scale-light" /></template>
