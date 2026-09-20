<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r63o7bckj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r63o7bckj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:heimdall-dark" /></template>
