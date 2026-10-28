<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep46uqbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep46uqbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:git-pull-request-draft-ai" /></template>
