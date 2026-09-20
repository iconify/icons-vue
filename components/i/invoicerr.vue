<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtyr96uhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xtyr96uhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoicerr" /></template>
