<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z43uply2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z43uply2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iplayarr-dark" /></template>
