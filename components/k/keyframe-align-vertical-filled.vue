<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2uj8-bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2uj8-bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:keyframe-align-vertical-filled" /></template>
