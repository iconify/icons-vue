<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmcda7bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmcda7bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:etsy" /></template>
