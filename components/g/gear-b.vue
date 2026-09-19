<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vva8lq2qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vva8lq2qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:gear-b" /></template>
