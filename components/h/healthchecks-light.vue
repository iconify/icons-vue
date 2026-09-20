<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcg2pob3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mcg2pob3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:healthchecks-light" /></template>
