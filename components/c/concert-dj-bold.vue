<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slk00objf.css';
import '../../css/w/wbyo_ts-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slk00objf"/><path class="wbyo_ts-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:concert-dj-bold" /></template>
