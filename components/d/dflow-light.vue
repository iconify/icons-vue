<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk9l67bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sk9l67bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dflow-light" /></template>
