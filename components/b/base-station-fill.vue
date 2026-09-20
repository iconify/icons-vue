<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z04b4pbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z04b4pbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:base-station-fill" /></template>
