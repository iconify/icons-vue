<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmk826btk.css';
import '../../css/i/i920hcbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hmk826btk"/><path class="i920hcbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:compass" /></template>
