<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3zilhxob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3zilhxob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cctv-gloss" /></template>
