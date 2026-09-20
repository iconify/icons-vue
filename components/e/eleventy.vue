<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tleff075d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tleff075d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eleventy" /></template>
