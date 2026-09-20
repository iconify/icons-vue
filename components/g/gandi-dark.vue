<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzxrsydfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mzxrsydfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gandi-dark" /></template>
