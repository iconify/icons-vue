<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umtprzi3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umtprzi3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hourglass" /></template>
