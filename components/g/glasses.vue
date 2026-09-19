<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsemixu9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tsemixu9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:glasses" /></template>
