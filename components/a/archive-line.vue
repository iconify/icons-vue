<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2s9tvbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2s9tvbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:archive-line" /></template>
