<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v86846boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v86846boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dropout-dark" /></template>
