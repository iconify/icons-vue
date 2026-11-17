<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbv2gkbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fbv2gkbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libre-closet" /></template>
