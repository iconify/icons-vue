<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5ac90b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5ac90b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caprover-light" /></template>
