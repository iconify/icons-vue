<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_jc64d5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_jc64d5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caprover-dark" /></template>
