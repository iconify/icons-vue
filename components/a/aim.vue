<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmk826btk.css';
import '../../css/n/nd2uznbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hmk826btk"/><path class="nd2uznbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:aim" /></template>
