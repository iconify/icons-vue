<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvz32_b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvz32_b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:envelope-open-text" /></template>
