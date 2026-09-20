<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6-3i_q-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6-3i_q-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:connector-1-bold" /></template>
