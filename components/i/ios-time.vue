<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5v5b0u5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y5v5b0u5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-time" /></template>
