<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmim1zbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dmim1zbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:arlo" /></template>
