<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0q5d6yma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0q5d6yma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flash-off-bold" /></template>
