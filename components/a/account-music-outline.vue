<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oogt8rbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oogt8rbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-music-outline" /></template>
