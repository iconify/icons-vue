<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcazbv6qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="wcazbv6qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hands-bubbles" /></template>
