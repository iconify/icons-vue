<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9uztebva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9uztebva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:concert-rock-1" /></template>
