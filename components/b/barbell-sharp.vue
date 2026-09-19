<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib84k77zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ib84k77zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:barbell-sharp" /></template>
