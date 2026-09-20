<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvuw72kws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvuw72kws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cards" /></template>
