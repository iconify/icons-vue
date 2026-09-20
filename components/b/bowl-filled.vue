<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usnvngb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usnvngb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bowl-filled" /></template>
