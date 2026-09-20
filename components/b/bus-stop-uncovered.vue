<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytdaeym0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytdaeym0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-stop-uncovered" /></template>
