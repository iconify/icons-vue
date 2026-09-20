<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od4ok1_9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="od4ok1_9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coneshare-light" /></template>
