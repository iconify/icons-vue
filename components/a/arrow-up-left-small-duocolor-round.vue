<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk_ur4bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk_ur4bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-left-small-duocolor-round" /></template>
