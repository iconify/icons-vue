<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1vzxi4tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1vzxi4tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ev-plug" /></template>
