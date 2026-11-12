<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-54ycbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-54ycbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cryptgeon-light" /></template>
