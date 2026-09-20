<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixbt-153a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixbt-153a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-diamond" /></template>
