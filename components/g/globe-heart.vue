<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjlborbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjlborbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:globe-heart" /></template>
