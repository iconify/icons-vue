<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9re8jzod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x9re8jzod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clipcascade-light" /></template>
