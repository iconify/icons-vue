<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwmhwbcdr.css';
import '../../css/e/erph9zbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwmhwbcdr"/><path class="erph9zbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-injection" /></template>
