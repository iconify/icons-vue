<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toni4fqyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="toni4fqyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:epic-games-dark" /></template>
