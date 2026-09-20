<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq9f5tbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hq9f5tbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:helium-mobile-light" /></template>
