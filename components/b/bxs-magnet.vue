<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi2b8lbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi2b8lbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-magnet" /></template>
