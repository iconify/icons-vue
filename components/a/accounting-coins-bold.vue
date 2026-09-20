<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fde5jabaf.css';
import '../../css/k/k4nhvymim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fde5jabaf"/><path class="k4nhvymim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:accounting-coins-bold" /></template>
