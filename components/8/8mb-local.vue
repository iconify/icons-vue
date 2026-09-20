<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci6-fubhr.css';
import '../../css/v/vqmzdlotb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ci6-fubhr"/><path class="vqmzdlotb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:8mb-local" /></template>
