<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em39fubym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em39fubym primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-dashed-sparkles-duotone" /></template>
