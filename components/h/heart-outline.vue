<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_9aq5btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_9aq5btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:heart-outline" /></template>
