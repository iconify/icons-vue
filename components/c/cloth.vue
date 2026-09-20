<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntuzksbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ntuzksbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cloth" /></template>
