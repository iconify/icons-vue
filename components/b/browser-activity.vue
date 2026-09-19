<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyues-25d.css';
import '../../css/l/l2z16-nsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyues-25d"/><path class="l2z16-nsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:browser-activity" /></template>
