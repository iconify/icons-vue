<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn3uzzukf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rn3uzzukf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-news-light" /></template>
