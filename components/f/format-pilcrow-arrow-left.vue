<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s25dc911s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s25dc911s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-pilcrow-arrow-left" /></template>
