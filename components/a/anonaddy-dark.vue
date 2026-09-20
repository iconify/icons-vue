<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rssfh2bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rssfh2bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anonaddy-dark" /></template>
