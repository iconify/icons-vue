<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmljcx80c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fmljcx80c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:glinr-light" /></template>
