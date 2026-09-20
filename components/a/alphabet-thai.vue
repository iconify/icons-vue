<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2-guw5mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2-guw5mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alphabet-thai" /></template>
