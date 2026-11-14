<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwh0ln4yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwh0ln4yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:attachment-off" /></template>
