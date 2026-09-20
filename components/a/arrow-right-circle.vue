<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aemjy9b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aemjy9b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-right-circle" /></template>
