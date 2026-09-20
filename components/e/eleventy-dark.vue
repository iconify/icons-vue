<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itn_tacpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itn_tacpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eleventy-dark" /></template>
