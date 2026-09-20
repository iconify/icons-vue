<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1p3sacgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1p3sacgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-plus-2" /></template>
