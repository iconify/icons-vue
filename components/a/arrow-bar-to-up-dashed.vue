<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-q20mb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-q20mb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-to-up-dashed" /></template>
