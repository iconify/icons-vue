<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cezc9fbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cezc9fbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libretranslate-dark" /></template>
