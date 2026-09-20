<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsj7abcli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsj7abcli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-off-outline" /></template>
