<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k36puzb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k36puzb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:mail-icon-2" /></template>
