<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7mqf2bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7mqf2bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grok-2-line" /></template>
