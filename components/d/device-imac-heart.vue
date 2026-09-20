<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow7g2ackt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow7g2ackt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-heart" /></template>
