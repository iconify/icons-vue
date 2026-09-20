<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa036zbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pa036zbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:airtrail" /></template>
