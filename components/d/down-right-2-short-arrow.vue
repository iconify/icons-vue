<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1-aahsdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1-aahsdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:down-right-2-short-arrow" /></template>
