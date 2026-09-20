<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nprivq5wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nprivq5wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cliparr-dark" /></template>
