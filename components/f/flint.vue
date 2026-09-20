<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me1w258bl.css';
import '../../css/e/e0ia1ccfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="me1w258bl"/><path class="e0ia1ccfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flint" /></template>
