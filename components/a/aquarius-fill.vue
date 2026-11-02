<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipim7xbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipim7xbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aquarius-fill" /></template>
