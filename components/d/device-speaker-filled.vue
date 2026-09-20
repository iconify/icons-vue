<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0qpvg3uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0qpvg3uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-speaker-filled" /></template>
