<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4xj07b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4xj07b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-left-two-tone" /></template>
