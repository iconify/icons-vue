<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6tbcgbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k6tbcgbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fortinet-light" /></template>
