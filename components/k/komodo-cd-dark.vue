<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx-f89bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cx-f89bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komodo-cd-dark" /></template>
