<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jczl-lz0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jczl-lz0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-forward-circle" /></template>
