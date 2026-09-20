<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4snjgbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w4snjgbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:evcc" /></template>
