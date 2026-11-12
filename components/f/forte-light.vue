<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbjl5x_qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gbjl5x_qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forte-light" /></template>
