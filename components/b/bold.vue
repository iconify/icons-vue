<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s018ey81a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s018ey81a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bold" /></template>
