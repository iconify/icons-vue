<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_1aioerq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_1aioerq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-g3" /></template>
