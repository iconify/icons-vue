<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7o6x_2pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z7o6x_2pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gotify-dark" /></template>
