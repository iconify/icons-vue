<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q61ylkipr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q61ylkipr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:donetick-light" /></template>
