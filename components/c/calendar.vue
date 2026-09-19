<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3c0_-nfk.css';
import '../../css/g/g6i8-p-_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="g3c0_-nfk"/><path class="g6i8-p-_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:calendar" /></template>
