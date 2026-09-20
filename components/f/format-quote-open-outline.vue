<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrlj9demd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrlj9demd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-quote-open-outline" /></template>
