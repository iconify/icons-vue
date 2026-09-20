<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u305y6bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u305y6bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-up-rhombus-filled" /></template>
