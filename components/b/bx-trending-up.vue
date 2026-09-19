<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqnt5cb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqnt5cb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-trending-up" /></template>
