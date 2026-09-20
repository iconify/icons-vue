<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6c8p4bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6c8p4bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gauge" /></template>
