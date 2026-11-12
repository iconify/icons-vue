<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrso21bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rrso21bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kanboard-dark" /></template>
