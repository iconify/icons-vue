<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxj25kbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cxj25kbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:listenarr-dark" /></template>
