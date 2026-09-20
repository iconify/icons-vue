<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga8f3jbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ga8f3jbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:home-information-dark" /></template>
