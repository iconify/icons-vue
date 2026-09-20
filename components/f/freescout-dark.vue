<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc6xymkfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uc6xymkfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freescout-dark" /></template>
