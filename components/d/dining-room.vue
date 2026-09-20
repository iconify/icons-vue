<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep01_69oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ep01_69oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:dining-room" /></template>
