<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxgk9xb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nxgk9xb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:event-tentative-mirrored" /></template>
