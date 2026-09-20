<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt6vwsbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt6vwsbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:attachment-bold" /></template>
