<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfv5wi-rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfv5wi-rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crowdstrike" /></template>
