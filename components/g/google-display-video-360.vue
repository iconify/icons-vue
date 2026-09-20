<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhqv_9bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhqv_9bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-display-video-360" /></template>
