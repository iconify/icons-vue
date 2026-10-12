<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2s5ueg_q.css';
import '../../css/v/vm8t9uryo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2s5ueg_q"/><path class="vm8t9uryo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dog-20" /></template>
