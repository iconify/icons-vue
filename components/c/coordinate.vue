<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8diq5roc.css';
import '../../css/x/xko87bc4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q8diq5roc"/><path class="xko87bc4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:coordinate" /></template>
