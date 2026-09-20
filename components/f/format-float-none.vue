<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwvs1xbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwvs1xbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-float-none" /></template>
