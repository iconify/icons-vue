<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9iyuzb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9iyuzb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:list-music-filled" /></template>
