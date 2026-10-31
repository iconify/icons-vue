<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb00t0bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb00t0bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-up-small-bulk-round" /></template>
