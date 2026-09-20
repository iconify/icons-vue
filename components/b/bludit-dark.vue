<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5k65pgym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j5k65pgym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bludit-dark" /></template>
