<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx5km29gc.css';
import '../../css/u/ua3nsqb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx5km29gc"/><path class="ua3nsqb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-slide-left-and-right-filled" /></template>
