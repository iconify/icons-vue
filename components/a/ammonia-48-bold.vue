<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlpv10bkk.css';
import '../../css/a/aai7kpb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vlpv10bkk"/><path class="aai7kpb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ammonia-48-bold" /></template>
