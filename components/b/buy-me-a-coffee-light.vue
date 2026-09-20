<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjum9-bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sjum9-bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buy-me-a-coffee-light" /></template>
