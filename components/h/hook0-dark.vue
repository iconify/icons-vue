<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co2lme0xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="co2lme0xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hook0-dark" /></template>
