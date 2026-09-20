<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cedh1bb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cedh1bb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-circle-outline" /></template>
