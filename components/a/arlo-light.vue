<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjaysdg3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mjaysdg3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:arlo-light" /></template>
