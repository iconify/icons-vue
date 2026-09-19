<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfdus8bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="lfdus8bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:facebook-box" /></template>
