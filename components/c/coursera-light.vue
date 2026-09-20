<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytgpocbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ytgpocbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coursera-light" /></template>
