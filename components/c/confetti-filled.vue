<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ije_0lbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ije_0lbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:confetti-filled" /></template>
