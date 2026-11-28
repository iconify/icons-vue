<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clngo6w0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clngo6w0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clapperboard" /></template>
