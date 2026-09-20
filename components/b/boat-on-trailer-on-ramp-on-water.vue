<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eowcfacat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eowcfacat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:boat-on-trailer-on-ramp-on-water" /></template>
