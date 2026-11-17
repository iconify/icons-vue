<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6y37ac6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6y37ac6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cadenza-dark" /></template>
