<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5sok3blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5sok3blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-pull-request-closed-round" /></template>
