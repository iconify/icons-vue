<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdfl41b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kdfl41b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bknd-light" /></template>
