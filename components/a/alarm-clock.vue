<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u148y6bbs.css';
import '../../css/i/id-v8e4aj.css';
import '../../css/h/h1jg740us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="u148y6bbs"><path class="id-v8e4aj"/><path class="h1jg740us"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:alarm-clock" /></template>
