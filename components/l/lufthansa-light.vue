<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at-g7wb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="at-g7wb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lufthansa-light" /></template>
