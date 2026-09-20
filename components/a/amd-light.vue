<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6_r9kvaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e6_r9kvaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amd-light" /></template>
