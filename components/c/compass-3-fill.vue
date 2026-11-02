<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok-qd1dri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-qd1dri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:compass-3-fill" /></template>
