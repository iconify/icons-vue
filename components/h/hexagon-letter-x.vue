<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9l4y-1ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9l4y-1ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-x" /></template>
