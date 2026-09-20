<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rngfsdb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rngfsdb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bbc-iplayer-logo-2" /></template>
