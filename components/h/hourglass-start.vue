<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2pcyob-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="q2pcyob-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:hourglass-start" /></template>
