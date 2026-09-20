<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdtld8bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdtld8bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-low-fill-2" /></template>
