<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kao537bdv.css';
import '../../css/b/bhrtkjeyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kao537bdv"/><path class="bhrtkjeyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lumio-dark" /></template>
