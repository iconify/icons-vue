<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z64_rrb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z64_rrb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-down-sharp-two-tone" /></template>
