<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqg93z-sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqg93z-sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:doorbell-solid" /></template>
