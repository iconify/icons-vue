<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn5ah_bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nn5ah_bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:golang-dark" /></template>
