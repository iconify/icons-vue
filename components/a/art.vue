<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sndv11bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sndv11bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:art" /></template>
