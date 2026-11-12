<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk7b67bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uk7b67bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bknd-dark" /></template>
