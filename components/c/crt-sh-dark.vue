<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcihm-0sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xcihm-0sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crt-sh-dark" /></template>
