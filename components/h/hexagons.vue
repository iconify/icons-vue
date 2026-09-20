<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a32w6l6cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a32w6l6cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagons" /></template>
