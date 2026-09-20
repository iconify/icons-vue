<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq5s4xbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq5s4xbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fence-filled" /></template>
