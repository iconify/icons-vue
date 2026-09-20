<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1w6ya-bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1w6ya-bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down-rhombus-filled" /></template>
