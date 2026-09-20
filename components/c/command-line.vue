<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf6hq7bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lf6hq7bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:command-line" /></template>
