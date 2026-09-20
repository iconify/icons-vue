<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0w2_eb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u0w2_eb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lululemon-light" /></template>
