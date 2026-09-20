<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1fhx14ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1fhx14ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-w-filled" /></template>
