<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1v28kbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1v28kbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-axis-3d" /></template>
