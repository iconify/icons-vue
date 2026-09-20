<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea_ia8ezp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ea_ia8ezp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fasten-health-dark" /></template>
