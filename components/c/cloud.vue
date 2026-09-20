<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u13qd4yvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u13qd4yvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud" /></template>
