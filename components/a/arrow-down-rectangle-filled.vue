<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iim0fhzkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iim0fhzkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-down-rectangle-filled" /></template>
